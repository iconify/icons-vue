<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyx3e6b3g.css';
import '../../css/w/wnjmof43i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyx3e6b3g"/><path class="wnjmof43i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:folder-add-bold" /></template>
