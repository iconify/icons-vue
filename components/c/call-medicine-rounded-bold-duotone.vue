<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkxo3pbyr.css';
import '../../css/x/x6g9eebag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fkxo3pbyr"/><path class="x6g9eebag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-medicine-rounded-bold-duotone" /></template>
