<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvy-dbcdt.css';
import '../../css/e/ebdqu7z2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvy-dbcdt"/><path clip-rule="evenodd" class="ebdqu7z2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:jar-of-pills-outline" /></template>
