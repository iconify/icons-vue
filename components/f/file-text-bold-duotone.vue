<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6gwrmjs.css';
import '../../css/c/cfsqh_tkm.css';
import '../../css/z/zw_fb9bav.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="cfsqh_tkm"/><path class="zw_fb9bav"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-text-bold-duotone" /></template>
