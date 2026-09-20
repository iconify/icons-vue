<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6ovqkmll.css';
import '../../css/b/bi7kcybaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6ovqkmll"/><path class="bi7kcybaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hail-fill" /></template>
