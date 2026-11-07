<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxw0gio2t.css';
import '../../css/k/k8vhtfbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxw0gio2t"/><path class="k8vhtfbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-bold-duotone" /></template>
