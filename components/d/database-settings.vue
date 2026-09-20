<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8ots_bdl.css';
import '../../css/w/w1qg11bis.css';
import '../../css/e/ehgylhzlx.css';
import '../../css/p/pkebo2bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8ots_bdl"/><path class="w1qg11bis"/><path clip-rule="evenodd" class="ehgylhzlx"/><path clip-rule="evenodd" class="pkebo2bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:database-settings" /></template>
