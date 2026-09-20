<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uitkfv-im.css';
import '../../css/n/n5mt1qbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uitkfv-im"/><path class="n5mt1qbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:book-open-alt-fill" /></template>
