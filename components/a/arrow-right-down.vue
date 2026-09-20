<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw_8fz9oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw_8fz9oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-right-down" /></template>
