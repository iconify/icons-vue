<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mblriccyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mblriccyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:giraffe-filled" /></template>
