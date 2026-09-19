<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re_szkbok.css';
import '../../css/t/tlsb-2bhs.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 re_szkbok"/><path class="clr-i-solid clr-i-solid-path-2 tlsb-2bhs"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:login-solid" /></template>
