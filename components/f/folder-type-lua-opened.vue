<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fpntqdbqk"/><path class="iu-5-cc_v"/><path class="qd99tz5pg"/><path class="krd-ckbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-lua-opened" /></template>
<style>
.fpntqdbqk {
  fill: var(--svg-color--6464d2, #6464d2);
  d: path("M29.5 5.5H18.2l-2.1 4.2H4.3v16.8h25.2zm-2.1 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1zm-1.7 4H.5l3.8 12.8h25.2z");
}

.iu-5-cc_v {
  fill: none;
  stroke: var(--svg-color--gray, gray);
  stroke-dasharray: 0.904;
  stroke-width: var(--svg-stroke-width--0-247px, 0.247px);
  d: path("M29.75 15.81a10.368 10.368 0 1 1-2.85-3.46");
}

.krd-ckbke {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.49 17.2a2.35 2.35 0 1 0 4.7 0a2.35 2.35 0 1 0-4.7 0m-3.14 7.33v-.59h-2.59v-4.67h-.68v5.26zm3.61 0v-3.78h-.6v2.09c0 .77-.4 1.27-1.03 1.27a.71.71 0 0 1-.78-.74v-2.62h-.6v2.86c0 .62.47 1.02 1.2 1.02a1.42 1.42 0 0 0 1.27-.69v.59zm4.4-.02v-.45l-.13.01q-.33 0-.33-.3v-2.09q-.01-1.03-1.43-1.04c-.91 0-1.47.35-1.51 1.23h.61c.05-.46.32-.67.89-.67q.82.01.84.56v.16c0 .25-.15.35-.62.41a4.5 4.5 0 0 0-1.22.23a.97.97 0 0 0-.67.99c0 .68.48 1.08 1.25 1.08a1.8 1.8 0 0 0 1.28-.55a.64.64 0 0 0 .62.5a1.5 1.5 0 0 0 .41-.08m-1.04-1.28a1.026 1.026 0 0 1-1.14.89c-.47 0-.75-.17-.75-.58c0-.39.27-.57.91-.66a3 3 0 0 0 .98-.21z");
}

.qd99tz5pg {
  fill: var(--svg-color--navy, navy);
  d: path("M12.51 20.52a8.015 8.015 0 1 0 16.03 0a8.015 8.015 0 1 0-16.03 0m13.68-8.01a2.349 2.349 0 1 0 4.7 0a2.349 2.349 0 1 0-4.7 0");
}

</style>
