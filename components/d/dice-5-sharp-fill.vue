<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwlqg5-8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cwlqg5-8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-5-sharp-fill" /></template>
