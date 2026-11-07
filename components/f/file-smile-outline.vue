<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz01z324w.css';
import '../../css/i/igtvqq5bu.css';
import '../../css/f/fpndi3bcf.css';
import '../../css/s/snslpzbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz01z324w"/><path class="igtvqq5bu"/><path clip-rule="evenodd" class="fpndi3bcf"/><path class="snslpzbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-smile-outline" /></template>
