<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py86dxbyc.css';
import '../../css/k/km474465y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py86dxbyc"/><path clip-rule="evenodd" class="km474465y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-plus" /></template>
