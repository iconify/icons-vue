<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3l4fgb5a.css';
import '../../css/k/k8xg7x5nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3l4fgb5a"/><path class="k8xg7x5nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:buildings-filled" /></template>
