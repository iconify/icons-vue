<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjfcwybnl.css';
import '../../css/v/vrncrobzx.css';
import '../../css/k/ki4mvymot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjfcwybnl"/><path class="vrncrobzx"/><path class="ki4mvymot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:jquery" /></template>
