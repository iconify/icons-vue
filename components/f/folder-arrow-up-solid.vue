<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjc9o4b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjc9o4b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-arrow-up-solid" /></template>
