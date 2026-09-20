<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvbrswb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvbrswb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope-open2" /></template>
