<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ik5l0cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ik5l0cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:heroku" /></template>
