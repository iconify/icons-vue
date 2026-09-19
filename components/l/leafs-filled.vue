<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aooua_bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aooua_bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:leafs-filled" /></template>
