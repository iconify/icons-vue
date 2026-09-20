<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox9ffzb9n.css';
import '../../css/o/otxlapboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ox9ffzb9n"/><path class="otxlapboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-boolean" /></template>
