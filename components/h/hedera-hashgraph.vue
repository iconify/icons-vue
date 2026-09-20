<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1okqdbgr.css';
import '../../css/b/bq-mafblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1okqdbgr"/><path clip-rule="evenodd" class="bq-mafblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hedera-hashgraph" /></template>
