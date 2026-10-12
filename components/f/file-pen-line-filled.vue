<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw4mfbbve.css';
import '../../css/i/iz0jpn4au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tw4mfbbve"/><path class="iz0jpn4au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-pen-line-filled" /></template>
