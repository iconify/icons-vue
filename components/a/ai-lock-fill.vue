<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ost-0qr-b.css';
import '../../css/r/r5tlw_31c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ost-0qr-b"/><path clip-rule="evenodd" class="r5tlw_31c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-lock-fill" /></template>
