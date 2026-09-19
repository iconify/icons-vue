<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meu8qvatp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="meu8qvatp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:bell" /></template>
