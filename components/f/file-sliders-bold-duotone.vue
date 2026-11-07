<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6gwrmjs.css';
import '../../css/x/xqwccrb2b.css';
import '../../css/y/ycy7myf2q.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path clip-rule="evenodd" class="xqwccrb2b"/><path clip-rule="evenodd" class="ycy7myf2q"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-sliders-bold-duotone" /></template>
