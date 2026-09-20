<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsrq7dtpz.css';
import '../../css/o/oto4ucbif.css';
import '../../css/i/iek1ggn7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsrq7dtpz"/><path class="oto4ucbif"/><path class="iek1ggn7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-at" /></template>
