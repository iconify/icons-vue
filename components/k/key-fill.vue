<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja3mrtbir.css';
import '../../css/n/nmhwd39xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ja3mrtbir"/><path class="nmhwd39xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:key-fill" /></template>
