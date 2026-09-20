<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zghy_mbjo"/><path class="lw-vphjpx"/><path class="kr4m6hi8m"/><ellipse class="do4-3ib5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-db" /></template>
<style>
.do4-3ib5j {
  cx: 23.4px;
  cy: 12.921px;
  fill: var(--svg-color--ffda44, #ffda44);
  rx: 7.472px;
  ry: 2.921px;
}

.kr4m6hi8m {
  fill: var(--svg-color--ffda44, #ffda44);
  d: path("M23.4 31c4.125 0 7.472-1.308 7.472-2.921v-2.127a8 8 0 0 1-1.151.571l-.118.047a17.6 17.6 0 0 1-6.2 1.013a17.6 17.6 0 0 1-6.2-1.013l-.118-.047a8 8 0 0 1-1.151-.571v2.128C15.928 29.692 19.275 31 23.4 31");
}

.lw-vphjpx {
  fill: var(--svg-color--ffda44, #ffda44);
  d: path("M17.822 19.942a15.9 15.9 0 0 0 5.578.895a15.9 15.9 0 0 0 5.578-.9c1.4-.545 1.894-1.151 1.894-1.5v-2.662a7.8 7.8 0 0 1-1.563.807a16.7 16.7 0 0 1-5.909.977a16.8 16.8 0 0 1-5.909-.975a7.7 7.7 0 0 1-1.563-.809v2.663c0 .355.497.962 1.894 1.504m0 5.029a11.7 11.7 0 0 0 1.95.556a19.6 19.6 0 0 0 7.257 0a11.7 11.7 0 0 0 1.95-.556c1.4-.545 1.894-1.151 1.894-1.5v-2.542a8 8 0 0 1-1.269.619a17.6 17.6 0 0 1-6.2 1.007a17.6 17.6 0 0 1-6.2-1.011a8 8 0 0 1-1.269-.619v2.545c-.007.35.49.953 1.887 1.501");
}

.zghy_mbjo {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
