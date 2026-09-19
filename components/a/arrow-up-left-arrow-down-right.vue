<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc02xp00d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rc02xp00d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-left-arrow-down-right" /></template>
