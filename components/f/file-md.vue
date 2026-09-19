<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di8ni_dks.css';
import '../../css/z/z_6vl9bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di8ni_dks"/><path class="z_6vl9bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-md" /></template>
