<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5_zthcmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="i5_zthcmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:edit" /></template>
