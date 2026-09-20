<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuqogfllb.css';
import '../../css/z/z2amuho-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuqogfllb"/><path clip-rule="evenodd" class="z2amuho-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:light-bulb-exclamation" /></template>
