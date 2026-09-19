<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9mpdcwxa.css';
import '../../css/y/yh9pzinki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="v9mpdcwxa"/><path class="yh9pzinki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:avatarman" /></template>
