<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm3zlkn7f.css';
import '../../css/s/sz_qvhbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm3zlkn7f"/><path class="sz_qvhbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-user-outline" /></template>
