<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv_bb_ldv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv_bb_ldv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:git-branch-solid" /></template>
