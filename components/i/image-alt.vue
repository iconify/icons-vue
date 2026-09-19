<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffa_0jn3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffa_0jn3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-alt" /></template>
