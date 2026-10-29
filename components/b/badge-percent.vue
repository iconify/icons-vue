<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsvhz9bpc.css';
import '../../css/u/ui3j74sqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsvhz9bpc wm-k"/><path class="ui3j74sqk wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:badge-percent" /></template>
