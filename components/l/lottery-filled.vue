<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z01kv1b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z01kv1b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lottery-filled" /></template>
