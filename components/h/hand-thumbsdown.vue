<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkhk-ku6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rkhk-ku6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-thumbsdown" /></template>
