<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_-x8vqlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_-x8vqlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-plus-solid" /></template>
