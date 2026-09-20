<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4vyrob7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4vyrob7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flask-2-off" /></template>
