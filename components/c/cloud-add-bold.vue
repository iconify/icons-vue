<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8lu4ibzi.css';
import '../../css/a/asyh4bbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8lu4ibzi"/><path class="asyh4bbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cloud-add-bold" /></template>
