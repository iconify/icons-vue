<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl9nzzbwz.css';
import '../../css/w/w65rdobqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl9nzzbwz"/><path clip-rule="evenodd" class="w65rdobqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:content-share-duotone" /></template>
