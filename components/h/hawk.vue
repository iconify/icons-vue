<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-0j_gbpc.css';
import '../../css/l/lxltxnh8y.css';
import '../../css/d/daur5ccoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-0j_gbpc"/><path clip-rule="evenodd" class="lxltxnh8y"/><path class="daur5ccoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hawk" /></template>
