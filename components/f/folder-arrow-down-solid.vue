<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6-rdobn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa6-rdobn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-arrow-down-solid" /></template>
