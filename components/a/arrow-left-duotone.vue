<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/git-dirdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="git-dirdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-left-duotone" /></template>
