<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag5uj2ugo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ag5uj2ugo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-2-filled" /></template>
