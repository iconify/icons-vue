<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_agx_bnn.css';
import '../../css/f/fv8j5jbkf.css';
import '../../css/n/n7rzczb-e.css';
import '../../css/w/wun81vb8v.css';
import '../../css/o/on2cwtbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_agx_bnn wm-a"/><path class="fv8j5jbkf wm-k"/><path class="n7rzczb-e wm-k"/><path class="wm-a wun81vb8v"/><path class="on2cwtbnl wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:handshake" /></template>
