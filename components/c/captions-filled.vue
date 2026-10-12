<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajg2szb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajg2szb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:captions-filled" /></template>
