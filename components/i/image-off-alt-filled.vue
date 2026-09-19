<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il0_djbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il0_djbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-off-alt-filled" /></template>
