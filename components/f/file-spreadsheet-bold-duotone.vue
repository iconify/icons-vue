<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6gwrmjs.css';
import '../../css/i/ixw1cy8fb.css';
import '../../css/g/g502-xb2c.css';
import '../../css/m/mdomo9bqv.css';
import '../../css/a/a04zgy3zm.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="ixw1cy8fb"/><path class="g502-xb2c"/><path class="mdomo9bqv"/><path class="a04zgy3zm"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-spreadsheet-bold-duotone" /></template>
