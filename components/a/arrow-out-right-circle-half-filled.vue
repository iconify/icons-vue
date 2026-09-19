<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c852q-rbq.css';
import '../../css/z/z7ybbhltq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c852q-rbq"/><path class="z7ybbhltq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-right-circle-half-filled" /></template>
