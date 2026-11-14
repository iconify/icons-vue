<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tn22_2dhz"/><path class="btn4gqb2m"/><path class="gcorstbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:macro-plus" /></template>
<style>
.btn4gqb2m {
  d: path("M11.5 8.25q.184 0 .368.018q.183.018.364.054q.18.036.357.089q.176.054.346.124t.333.158t.315.189q.154.102.296.219t.273.247t.247.273t.219.296t.189.315q.087.163.158.333q.07.17.124.346q.053.177.089.357q.036.181.054.364q.018.184.018.368q0 .244-.032.486q-.031.243-.094.479t-.156.462t-.214.438q-.122.212-.27.406t-.32.368t-.364.323t-.404.273m-1.152.441q-.368.074-.744.074q-.184 0-.368-.018q-.183-.018-.364-.054q-.18-.036-.357-.089q-.176-.054-.346-.124t-.333-.158t-.315-.189q-.154-.102-.296-.219t-.273-.247t-.247-.273t-.219-.296t-.189-.315q-.087-.163-.158-.333q-.07-.17-.124-.346q-.053-.177-.089-.357q-.036-.181-.054-.364q-.018-.184-.018-.368");
}

.gcorstbxc {
  d: path("m5.75 14l2-2l2 2M18 15v6m-3-3h6");
}

.tn22_2dhz {
  d: path("M12.2 20H2.5V4h19v11.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
