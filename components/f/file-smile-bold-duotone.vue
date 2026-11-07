<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6gwrmjs.css';
import '../../css/z/zm8jc6bmu.css';
import '../../css/w/wo04hje9a.css';
import '../../css/t/t0pm9yw2p.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="zm8jc6bmu"/><path class="wo04hje9a"/><path class="t0pm9yw2p"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-smile-bold-duotone" /></template>
