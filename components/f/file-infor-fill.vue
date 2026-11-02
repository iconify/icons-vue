<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p13sy1bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p13sy1bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-infor-fill" /></template>
