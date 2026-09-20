<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5r2mqckq"/><path class="i35egybgu"/><path class="km83hhe5p"/><path class="j21pv0h1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-images-opened" /></template>
<style>
.f5r2mqckq {
  fill: var(--svg-color--7bdbc0, #7bdbc0);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.i35egybgu {
  fill: var(--svg-color--7bdbc0, #7bdbc0);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.j21pv0h1t {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.674 17.8a1.653 1.653 0 1 0 .845.467a1.66 1.66 0 0 0-.845-.467m-4.591 8.667L18 20.786l-6.062 8.428h8.174q.987-1.374 1.976-2.747m2.955-3.076l-4.188 5.824h8.377q-2.094-2.915-4.189-5.824");
}

.km83hhe5p {
  fill: var(--svg-color--2dcc9f, #2dcc9f);
  d: path("M31 15.778V31H10V15.777h21");
}

</style>
