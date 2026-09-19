<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s33pr9m8e.css';
import '../../css/d/df5dkmbjb.css';
import '../../css/b/by50vbcxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s33pr9m8e"/><path class="df5dkmbjb"/><path class="by50vbcxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coins-filled" /></template>
