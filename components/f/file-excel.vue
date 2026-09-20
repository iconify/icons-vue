<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds2udfbbe.css';
import '../../css/g/gr02mac6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds2udfbbe"/><path class="gr02mac6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:file-excel" /></template>
