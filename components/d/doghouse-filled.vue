<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd9s1hbcj.css';
import '../../css/m/m4hvdnqig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gd9s1hbcj"/><path class="m4hvdnqig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:doghouse-filled" /></template>
