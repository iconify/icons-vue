<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uecsehbiq.css';
import '../../css/s/s9ro2bzzp.css';
import '../../css/l/ll5_hob1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uecsehbiq"/><path clip-rule="evenodd" class="s9ro2bzzp"/><path clip-rule="evenodd" class="ll5_hob1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-lock" /></template>
