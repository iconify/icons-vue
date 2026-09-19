<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liblnjhws.css';
import '../../css/f/fjtbb1h3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liblnjhws"/><path class="fjtbb1h3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:dns" /></template>
