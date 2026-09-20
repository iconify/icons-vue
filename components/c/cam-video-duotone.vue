<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so43afb2h.css';
import '../../css/u/u399owb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so43afb2h"/><path clip-rule="evenodd" class="u399owb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cam-video-duotone" /></template>
