<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af4sfbb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="af4sfbb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-down-right-light" /></template>
