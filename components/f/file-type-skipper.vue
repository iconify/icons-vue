<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="haw417v8a"/><path class="mdbm_6oud"/><path class="rnv5jbc0h"/><path class="b9zbq6bvv"/><path class="cdvdtzk6j"/><path class="hnj2g5r5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-skipper" /></template>
<style>
.b9zbq6bvv {
  d: path("M25.462 17.65h-.066l-18.77-.11c-.21-.107-5.106-2.637-4.563-4.99c.49-2.106 4.968-3.206 13.702-3.362c8.908-.159 13.539.826 14.148 3.016c.68 2.453-4.187 5.298-4.394 5.415Z");
}

.cdvdtzk6j {
  fill: var(--svg-color--f2f2f0, #f2f2f0);
  d: path("M6.738 17.321s-14.63-7.464 9.032-7.887c24.17-.434 9.626 7.972 9.626 7.972Z");
}

.haw417v8a {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.3 22.828h-.421c-8.712-.129-9.992-2.958-10.042-3.078L6.3 17.035l19.22.086l-.187 2.72c-.036.161-.81 2.987-8.034 2.987");
}

.hnj2g5r5j {
  d: path("M15.197 13.57c-.114 1.599 1.723 2.066 1.723 2.066s1.812-.56 1.615-2.15l.209-.006l-.272-.305l-.303.32l.22-.006a1.54 1.54 0 0 1-1.185 1.363l-.235-2.88l.428-.01a.12.12 0 1 0 0-.153l-.44.012l-.01-.139a.327.327 0 1 0-.24 0v.143l-.398.01a.12.12 0 1 0 .008.153l.385-.01l-.076 2.897c-1.173-.355-1.27-1.178-1.276-1.308l.22-.006l-.32-.303l-.255.318Zm1.632-2.02a.175.175 0 1 1 .17-.178a.177.177 0 0 1-.17.18Z");
}

.mdbm_6oud {
  d: path("m6.6 17.275l.463 2.375s1.169 2.802 9.82 2.93c7.508.11 8.205-2.757 8.205-2.757l.17-2.46Z");
}

.rnv5jbc0h {
  fill: var(--svg-color--fed94e, #fed94e);
  d: path("m6.808 18.34l18.388-.023l-.04.533l-18.275-.103z");
}

</style>
