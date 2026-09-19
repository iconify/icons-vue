<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw50q5sdt.css';
import '../../css/t/tcsakibxe.css';
import '../../css/x/xoc373bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aw50q5sdt"/><path class="tcsakibxe"/><path class="xoc373bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-filing" /></template>
