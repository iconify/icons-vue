<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6mz_vjes.css';
import '../../css/c/c441vmfnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6mz_vjes"/><path clip-rule="evenodd" class="c441vmfnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:bank-filled" /></template>
