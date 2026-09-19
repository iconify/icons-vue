<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9b-hkiwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9b-hkiwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-close-fill" /></template>
