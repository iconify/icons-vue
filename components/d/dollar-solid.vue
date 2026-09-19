<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1flr7boj.css';
import '../../css/r/rtokti3yj.css';
import '../../css/l/lgf9ojfoo.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 u1flr7boj"/><path class="clr-i-solid clr-i-solid-path-2 rtokti3yj"/><path class="clr-i-solid clr-i-solid-path-3 lgf9ojfoo"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:dollar-solid" /></template>
