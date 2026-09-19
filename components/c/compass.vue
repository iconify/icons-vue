<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nabybfvfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="nabybfvfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:compass" /></template>
