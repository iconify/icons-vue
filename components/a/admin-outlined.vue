<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp_zsmb1r.css';
import '../../css/h/hoky06fxe.css';
import '../../css/g/gxeqjdbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_zsmb1r"/><circle class="hoky06fxe"/><path class="gxeqjdbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:admin-outlined" /></template>
