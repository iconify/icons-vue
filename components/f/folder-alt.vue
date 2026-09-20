<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veiu-2wux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="veiu-2wux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-alt" /></template>
