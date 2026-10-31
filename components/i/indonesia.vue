<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr8ohcc6r.css';
import '../../css/t/t39v8hihk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jr8ohcc6r"/><path class="t39v8hihk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:indonesia" /></template>
