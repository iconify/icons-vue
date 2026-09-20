<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcw8iw7rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcw8iw7rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-3-filled" /></template>
