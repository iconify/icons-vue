<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1mcpb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-lock-rounded" /></template>
<style>
.oa1mcpb-y {
  fill: currentColor;
  d: path("M12 11L4.82 6.32q-.195-.122-.402-.045t-.264.289q-.077.148-.025.297t.194.235l7.229 4.733q.214.13.45.13q.235 0 .446-.13l7.229-4.733q.142-.086.194-.245t-.025-.307q-.057-.211-.264-.278t-.401.053zm6.5 8q-.376 0-.63-.254q-.255-.255-.255-.63v-3q0-.387.298-.636t.703-.25v-1.114q0-.778.549-1.331q.549-.554 1.335-.554t1.336.554t.549 1.33v1.116q.405 0 .702.249t.297.636v3q0 .375-.254.63q-.254.254-.63.254zm.885-4.77h2.23v-1.107q0-.471-.326-.797T20.5 12t-.79.326t-.326.797zM4.615 19q-.666 0-1.14-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5h14.77q.666 0 1.14.475T21 6.615v2.116q0 .212-.144.356t-.356.144q-2.027 0-3.456 1.462t-1.429 3.525v3.974q0 .344-.232.576t-.575.232z");
}

</style>
