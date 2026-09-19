<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/actsv6yen.css';
import '../../css/l/ljarxcchb.css';
import '../../css/q/qtehtydtc.css';
import '../../css/q/qkqdoq0od.css';
import '../../css/l/lljzobcwc.css';
import '../../css/k/k9oz9h86c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="actsv6yen"/><path class="ljarxcchb"/><path class="qtehtydtc"/><path class="qkqdoq0od"/><path class="lljzobcwc"/><path class="k9oz9h86c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:calendar" /></template>
