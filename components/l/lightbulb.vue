<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/a/ayb8wv.css';
import '../../css/i/ip662n.css';
import '../../css/s/so-from-46.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ayb8wv"/><path class="a0m25c ip662n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:lightbulb" /></template>
