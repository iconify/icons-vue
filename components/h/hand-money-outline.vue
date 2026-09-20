<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjsswl0up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjsswl0up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-money-outline" /></template>
