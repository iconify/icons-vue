<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cowqw2bkl.css';
import '../../css/k/knoj0abei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cowqw2bkl"/><path class="knoj0abei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:magic-wand-filled" /></template>
