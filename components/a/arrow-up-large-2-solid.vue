<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ln9i94v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_ln9i94v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-up-large-2-solid" /></template>
