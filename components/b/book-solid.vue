<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd1q9wb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd1q9wb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:book-solid" /></template>
