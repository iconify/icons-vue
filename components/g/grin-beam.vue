<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stilfpl4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="stilfpl4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-beam" /></template>
