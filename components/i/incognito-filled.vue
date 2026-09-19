<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9ycocbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9ycocbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:incognito-filled" /></template>
