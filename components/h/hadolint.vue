<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzr61tbtm.css';
import '../../css/d/d-6vdibyb.css';
import '../../css/y/yb06lccjp.css';
import '../../css/t/tcn-xl5yi.css';
import '../../css/x/xiamkcxub.css';
import '../../css/y/yqfxoj6jk.css';
import '../../css/h/h53c51bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jzr61tbtm"/><path class="d-6vdibyb"/><path class="yb06lccjp"/><path class="tcn-xl5yi"/><path class="xiamkcxub"/><path class="yqfxoj6jk"/><path class="h53c51bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hadolint" /></template>
