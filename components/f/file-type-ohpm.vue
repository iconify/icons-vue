<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGiwkXSbzl" x1="-.6" x2="161" y1="66.8" y2="66.8" gradientUnits="userSpaceOnUse"><stop offset="0" class="m3937pbho"/><stop offset=".9" class="uumho3jtv"/></linearGradient></defs><path fill="url(#SVGiwkXSbzl)" transform="translate(2 4.4)scale(.174)" class="rc6ymnums"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ohpm" /></template>
<style>
.m3937pbho {
  stop-color: var(--svg-color--3fa9f5, #3fa9f5);
}

.rc6ymnums {
  fill-rule: evenodd;
  d: path("M131.4 74h-13.6q-.4 0-.6.4v.2l-1 5.2l-.5 1.5l-.2.6l-.2.6l-.4 1.2l-.2.7l-.5 1.2l-.2.6l-.8 1.8l-.2.5l-.6 1.4a52 52 0 0 1-8 11.8l-1.3 1.4l-1.5 1.5l-.2.2l-1.4 1.3l-.6.5l-1.2 1l-.7.5l-1 .8l-.8.5l-1.2.8l-.6.4l-1.6 1l-.3.2l-2 1l-.6.4l-1.4.7l-.8.3l-1.3.6l-.8.3l-1.4.5l-.8.3l-1.6.5l-.6.2l-2.2.6H78l-1.8.5h-.8l-1.5.4h-1l-1.4.3h-1l-1.5.2h-3.2a52 52 0 1 1 0-104h4.8l.9.2l1.5.2h.9l1.5.4h.8l1.8.5h.5l2.2.7l.7.2l1.6.5l.8.3l1.4.5l.8.3l1.3.6l.8.3l1.4.7l.6.3l2 1.1l.3.2l1.7 1l.6.4l1.2.8l.7.5l1 .8l.5.4L100 27l1.8 1.6l1.2 1.2l.4.2h17.3q.5 0 .6-.6v-.3a59 59 0 0 0-5-6.3l-1.7-1.8l-.5-.5l-.5-.6l-.2-.2l-.2-.3l-2.3-2.2l-.3-.4l-2-1.7l-.4-.3l-.3-.2l-.6-.5l-1.2-.9l-.8-.6l-.5-.4l-.5-.3l-.7-.5l-1.4-.9l-.7-.4h-.2l-.5-.5L98 8l-1.8-.9l-.7-.3l-.3-.2h-.3l-.5-.4l-1.8-.8H92l-1.3-.6l-1-.4H89l-.3-.4l-1.9-.7l-.5-.2h-.2l-.3-.2l-.9-.3l-1.8-.5H83l-2-.5l-.8-.2h-.3l-.3-.2H79l-2-.5h-.7L74.9.4L73.6.2h-.8L70.7 0h-4.2a66.5 66.5 0 1 0 0 133h6.4l2-.2h.5l1.7-.2h1.2l.8-.2l1.1-.2h.9l2-.5h.6l1.4-.5l.6-.2h.3l.4-.2l.6-.2l1.2-.4h.4l.1-.2h.2l2-.8h.1l.2-.1l.4-.2l1.1-.5l.6-.3l.4-.2l.3-.2l.5-.2l1.3-.6h.3v-.1l1.8-1h.2l.3-.2l2.3-1.3l.4-.3h.2l.4-.4l1.2-.7l1.3-1l.4-.2h.2l.3-.4l2.2-1.6l.3-.3h.2l.4-.5l1.2-1l1.1-1l.4-.3l.2-.2l.3-.3l2-2l.1-.1h.1l.3-.5l1.2-1.2l.8-1l.3-.4l.2-.2l.4-.4l1.7-2.1l.2-.2l.2-.4l1.1-1.5l.8-1l.3-.4l.3-.4l.3-.4a64 64 0 0 0 7.2-14.7V89l.3-.8l.5-1.6v-.4l.2-.9l.4-1.4v-.3l.2-.3l.4-1.8v-.4l.2-.8l.5-3l.3-2.2q.6-.1.5-.7t-.7-.5zm-44-16.4l.6 1.6h15V59q-1.5-7.3-5.7-13.5l-.6-1h-23h.3c6.1 2.4 10.9 7 13.5 13zm9.8 30.1q4.2-6.2 5.7-13.5V74H88l-.6 1.8A24 24 0 0 1 75 88.1l-1 .4h22.7zm49.3-29.3v1H161q-.5-6-1.7-12l-.6-2.4h-14.8l.4 1.5a80 80 0 0 1 2 11.9zm0 15.5V75q-.6 6-2.1 12l-.4 1.5h14.8l.6-2.5q1.3-5.9 1.6-11.9V74zm-17.7-29v-.2H113l.3.7a52 52 0 0 1 4 13.4v.7H132l-.4-2.8a68 68 0 0 0-3-11.6z");
}

.uumho3jtv {
  stop-color: var(--svg-color--7ac943, #7ac943);
}

</style>
