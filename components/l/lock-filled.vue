<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hos5qbbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hos5qbbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-filled" /></template>
