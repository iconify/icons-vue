<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu79aub5k.css';
import '../../css/y/y801r3qvz.css';
import '../../css/m/mbfprhq2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xu79aub5k"/><path class="y801r3qvz"/><path clip-rule="evenodd" class="mbfprhq2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-tree-outline" /></template>
