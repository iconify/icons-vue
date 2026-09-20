<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b26ky1b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b26ky1b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-u-turn-right-sharp-fill" /></template>
