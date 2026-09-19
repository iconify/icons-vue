<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0tialbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0tialbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:columns-four-filled" /></template>
