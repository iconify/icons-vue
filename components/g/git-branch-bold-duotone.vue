<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpe08f7jm.css';
import '../../css/j/jj7xoyfhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpe08f7jm"/><path clip-rule="evenodd" class="jj7xoyfhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-branch-bold-duotone" /></template>
