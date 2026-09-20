<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfmahnb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfmahnb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-numbers-solid" /></template>
