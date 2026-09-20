<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs1umdg9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs1umdg9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-down-duotone" /></template>
