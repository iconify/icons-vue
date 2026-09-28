<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mp7pexwsr"/><path class="nxpo6w7bf"/><path class="me53jrbcw"/><path class="d4uptizct"/><path class="w15cptbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-alpine-opened" /></template>
<style>
.d4uptizct {
  fill: var(--svg-color--0d597f, #0d597f);
  d: path("M17.6 24.1v-2.21l-1.59 1.59q.257.178.486.297q.229.12.427.189q.2.07.369.1q.17.03.311.031m8.14-.184a.8.8 0 0 0 .174.099q.084.036.209.063t.296.029q.142.001.313-.028t.373-.099q.201-.07.433-.19t.493-.3l-1.21-1.18l-4.01-4.02l-1.76 1.76l-2.37-2.45l-5.95 5.88q.261.18.492.3t.433.19q.2.07.373.099q.172.029.313.028q.17-.001.296-.029a1.1 1.1 0 0 0 .336-.128l.047-.034l2.69-2.69l.961-.92l2.66 2.66l.93.955a.8.8 0 0 0 .174.099q.084.036.21.063q.125.028.295.029q.143.001.313-.028q.172-.03.373-.099q.202-.07.433-.19q.232-.12.493-.3l-2.14-2.09l.397-.398l1.85 1.85zm-.023-11.1l5.25 9.09l-5.25 9.09h-10.5l-5.25-9.09l5.25-9.09z");
}

.me53jrbcw {
  d: path("M12.8 17.6h15.3v6.5H12.8z");
}

.mp7pexwsr {
  fill: var(--svg-color--7abfdc, #7abfdc);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.nxpo6w7bf {
  fill: var(--svg-color--7abfdc, #7abfdc);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.w15cptbxy {
  fill: var(--svg-color--0d587d, #0d587d);
  d: path("m22.5 21.5l-1.4-1.4l.1-.1l1.41 1.39z");
}

</style>
