<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpe-v65l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcpe-v65l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:caret-up-light" /></template>
