<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkrwubblf.css';
import '../../css/j/jm1k0nbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wkrwubblf"/><path class="jm1k0nbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:android-fill" /></template>
