<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwt0w95mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwt0w95mp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-terminator-duotone" /></template>
