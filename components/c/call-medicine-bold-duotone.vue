<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-_et2sc.css';
import '../../css/f/fkxo3pbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-_et2sc"/><path clip-rule="evenodd" class="fkxo3pbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-medicine-bold-duotone" /></template>
