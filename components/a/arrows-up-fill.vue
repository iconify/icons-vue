<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s74ucqtbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s74ucqtbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-up-fill" /></template>
