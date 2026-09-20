<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itmvxw0rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itmvxw0rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anaconda" /></template>
