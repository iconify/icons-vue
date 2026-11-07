<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7lt-t-fe.css';
import '../../css/b/b-rzfvbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7lt-t-fe"/><path class="b-rzfvbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:braces-bold" /></template>
