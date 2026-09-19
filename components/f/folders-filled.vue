<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k16xm7bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k16xm7bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folders-filled" /></template>
