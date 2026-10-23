<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5u0jbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5u0jbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:git-pull-request" /></template>
