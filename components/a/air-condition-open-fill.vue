<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b29sb_hun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b29sb_hun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-condition-open-fill" /></template>
