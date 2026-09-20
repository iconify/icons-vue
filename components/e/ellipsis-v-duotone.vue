<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k29omfbdq.css';
import '../../css/v/v0quseb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k29omfbdq"/><path clip-rule="evenodd" class="v0quseb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-v-duotone" /></template>
